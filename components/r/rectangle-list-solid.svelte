<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqq8yzb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fqq8yzb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:rectangle-list-solid" {...props}></Icon>
