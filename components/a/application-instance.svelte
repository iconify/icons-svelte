<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jab5w2bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jab5w2bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:application-instance" {...props}></Icon>
