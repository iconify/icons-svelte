<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngp3jeu8h.css';
import '../../css/i/ixkzetvqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ngp3jeu8h"/><path class="ixkzetvqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloud-download" {...props}></Icon>
