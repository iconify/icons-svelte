<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl4ux5b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pl4ux5b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:project-fill" {...props}></Icon>
