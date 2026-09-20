<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooemsqbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooemsqbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:iron" {...props}></Icon>
