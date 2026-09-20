<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcho26b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcho26b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:clojure" {...props}></Icon>
