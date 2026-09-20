<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn190jbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn190jbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:leptos" {...props}></Icon>
