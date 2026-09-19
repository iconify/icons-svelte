<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz83udbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iz83udbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:exclamation-circle-solid" {...props}></Icon>
