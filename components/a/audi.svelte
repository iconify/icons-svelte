<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqln19cle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqln19cle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:audi" {...props}></Icon>
