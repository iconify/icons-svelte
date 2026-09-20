<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l18em4bxj.css';
import '../../css/t/ts9-onmui.css';
import '../../css/r/rkzw689zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l18em4bxj"/><path class="ts9-onmui"/><path class="rkzw689zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:data-science" {...props}></Icon>
