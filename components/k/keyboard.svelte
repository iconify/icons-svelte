<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inl2g9ceq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inl2g9ceq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:keyboard" {...props}></Icon>
