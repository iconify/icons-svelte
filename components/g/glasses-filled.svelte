<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4vl4e8qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4vl4e8qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:glasses-filled" {...props}></Icon>
