<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5ijgqb1h.css';
import '../../css/t/tgz0bac_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5ijgqb1h"/><path class="tgz0bac_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:invoice-light" {...props}></Icon>
