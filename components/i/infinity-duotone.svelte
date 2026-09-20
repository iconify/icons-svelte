<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dor5b2bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dor5b2bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:infinity-duotone" {...props}></Icon>
