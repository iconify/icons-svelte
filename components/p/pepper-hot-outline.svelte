<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilbxhgz6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilbxhgz6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:pepper-hot-outline" {...props}></Icon>
