<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d37zg4ilz.css';
import '../../css/f/fe11hu57u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d37zg4ilz"/><circle class="fe11hu57u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:info-large" {...props}></Icon>
