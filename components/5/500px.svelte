<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojriq_b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ojriq_b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:500px" {...props}></Icon>
