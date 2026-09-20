<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odvk9h54r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odvk9h54r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds" {...props}></Icon>
