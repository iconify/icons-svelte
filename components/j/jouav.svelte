<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlxtq4bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlxtq4bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jouav" {...props}></Icon>
