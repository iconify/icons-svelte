<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta49hdc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ta49hdc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:paycheck" {...props}></Icon>
