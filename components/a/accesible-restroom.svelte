<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkryll1rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkryll1rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:accesible-restroom" {...props}></Icon>
