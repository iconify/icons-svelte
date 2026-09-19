<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9atepzeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v9atepzeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:contacts-outline" {...props}></Icon>
