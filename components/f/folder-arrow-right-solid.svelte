<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udqwx6wsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udqwx6wsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:folder-arrow-right-solid" {...props}></Icon>
