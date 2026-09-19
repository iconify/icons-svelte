<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekmwabpqj.css';
import '../../css/p/pg8vlgzhf.css';
import '../../css/e/ehqo78bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekmwabpqj"/><path clip-rule="evenodd" class="pg8vlgzhf"/><path class="ehqo78bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notification-on-outline" {...props}></Icon>
