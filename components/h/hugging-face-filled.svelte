<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5zngn6ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v5zngn6ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:hugging-face-filled" {...props}></Icon>
