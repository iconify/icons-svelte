<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcj7e4vyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcj7e4vyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:briefcase-solid" {...props}></Icon>
