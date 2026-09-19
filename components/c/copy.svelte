<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaq7sqjqw.css';
import '../../css/s/sn777jbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaq7sqjqw"/><path class="sn777jbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:copy" {...props}></Icon>
