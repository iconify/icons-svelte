<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbs8e4bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":400};
const content = `<path class="lbs8e4bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:miro-light" {...props}></Icon>
