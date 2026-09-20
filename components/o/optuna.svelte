<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhpbq_pxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhpbq_pxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:optuna" {...props}></Icon>
