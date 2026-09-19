<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8fzu_bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8fzu_bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrows-reload-01" {...props}></Icon>
