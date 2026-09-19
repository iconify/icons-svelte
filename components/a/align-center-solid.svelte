<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmpvxvbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmpvxvbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:align-center-solid" {...props}></Icon>
