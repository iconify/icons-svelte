<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmkeibccw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wmkeibccw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:flag-outline" {...props}></Icon>
