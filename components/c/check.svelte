<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaim9281v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaim9281v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:check" {...props}></Icon>
