<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef1d_0bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef1d_0bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:capacitor" {...props}></Icon>
