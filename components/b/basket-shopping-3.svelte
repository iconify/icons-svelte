<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1egrjbgw.css';
import '../../css/d/drbq42kov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1egrjbgw"/><path class="drbq42kov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:basket-shopping-3" {...props}></Icon>
