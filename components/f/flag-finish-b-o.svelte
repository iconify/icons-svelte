<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dszoyk3rx.css';
import '../../css/o/oc7q_ob4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="dszoyk3rx"/><path class="oc7q_ob4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flag-finish-b-o" {...props}></Icon>
