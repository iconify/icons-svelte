<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln608z_bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln608z_bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-24" {...props}></Icon>
