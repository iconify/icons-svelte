<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udbs4h_qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udbs4h_qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coggle" {...props}></Icon>
