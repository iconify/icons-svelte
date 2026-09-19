<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plnf21w4w.css';
import '../../css/f/fowt9fbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plnf21w4w"/><path class="fowt9fbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-touch-filled" {...props}></Icon>
