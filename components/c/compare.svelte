<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqt5a61jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b eqt5a61jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:compare" {...props}></Icon>
