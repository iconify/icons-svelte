<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umx-hub4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umx-hub4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:briefcase-alt" {...props}></Icon>
