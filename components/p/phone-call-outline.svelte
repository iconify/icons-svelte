<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np3fkg3rl.css';
import '../../css/z/z6n--qb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np3fkg3rl"/><path class="z6n--qb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:phone-call-outline" {...props}></Icon>
