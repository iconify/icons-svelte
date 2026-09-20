<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w92k9abfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w92k9abfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:esoteric-software" {...props}></Icon>
