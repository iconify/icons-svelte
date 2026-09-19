<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np3fkg3rl.css';
import '../../css/t/tht3gpbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np3fkg3rl"/><path class="tht3gpbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:phone-call-fill" {...props}></Icon>
