<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q83hv0ath.css';
import '../../css/c/cj7oqvbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q83hv0ath"/><path class="cj7oqvbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-link" {...props}></Icon>
