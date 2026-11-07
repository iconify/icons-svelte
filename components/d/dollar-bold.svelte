<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlc6xfqvl.css';
import '../../css/q/qqluwf17f.css';
import '../../css/r/rwbdnz60g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlc6xfqvl"/><path class="qqluwf17f"/><path clip-rule="evenodd" class="rwbdnz60g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dollar-bold" {...props}></Icon>
