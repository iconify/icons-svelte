<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plsckdbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plsckdbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cast" {...props}></Icon>
