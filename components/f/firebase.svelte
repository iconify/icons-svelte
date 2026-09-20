<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4v9t8bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4v9t8bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:firebase" {...props}></Icon>
