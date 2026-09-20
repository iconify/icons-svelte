<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc7as45mv.css';
import '../../css/n/nsrryibqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc7as45mv"/><path clip-rule="evenodd" class="nsrryibqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:delete-alarm-fill" {...props}></Icon>
