<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9dbdkbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9dbdkbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:moonshotai" {...props}></Icon>
