<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibu_n4bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibu_n4bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ont" {...props}></Icon>
