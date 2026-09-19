<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwu26er0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwu26er0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:briefcase-solid" {...props}></Icon>
