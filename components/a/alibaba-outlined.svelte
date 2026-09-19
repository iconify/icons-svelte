<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukbwaaceu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ukbwaaceu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:alibaba-outlined" {...props}></Icon>
