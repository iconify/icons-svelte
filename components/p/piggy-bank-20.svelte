<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqqn4975g.css';
import '../../css/h/hgn5lvw7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sqqn4975g"/><path class="hgn5lvw7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:piggy-bank-20" {...props}></Icon>
