<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zujkk5zci.css';
import '../../css/e/etr_cu8yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zujkk5zci"/><path class="etr_cu8yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-button-left-16" {...props}></Icon>
