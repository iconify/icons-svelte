<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd4m4tkzl.css';
import '../../css/e/ebd7f4inr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd4m4tkzl"/><path class="ebd7f4inr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:android-alt" {...props}></Icon>
