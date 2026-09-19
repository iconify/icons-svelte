<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur8-5xb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur8-5xb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pendant-cher" {...props}></Icon>
