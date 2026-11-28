<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb6cpgbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb6cpgbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clapperboard-check" {...props}></Icon>
