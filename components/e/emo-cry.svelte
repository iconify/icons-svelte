<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo2ttybuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":851,"height":1000};
const content = `<path class="qo2ttybuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-cry" {...props}></Icon>
