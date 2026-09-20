<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5ookx5_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-4};
const content = `<path class="a5ookx5_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:layers-f" {...props}></Icon>
