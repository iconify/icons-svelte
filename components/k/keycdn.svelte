<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aned08bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aned08bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:keycdn" {...props}></Icon>
