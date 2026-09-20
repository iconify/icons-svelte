<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw2lnbcyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw2lnbcyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pagekit" {...props}></Icon>
