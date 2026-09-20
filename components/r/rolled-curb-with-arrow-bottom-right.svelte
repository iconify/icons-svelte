<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7chzchow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v7chzchow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rolled-curb-with-arrow-bottom-right" {...props}></Icon>
