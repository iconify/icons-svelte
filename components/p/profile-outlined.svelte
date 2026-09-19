<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5c6rjbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i5c6rjbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:profile-outlined" {...props}></Icon>
