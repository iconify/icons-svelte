<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qftch_bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qftch_bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:react-hook-form" {...props}></Icon>
