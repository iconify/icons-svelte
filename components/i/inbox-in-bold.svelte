<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo16j27lx.css';
import '../../css/j/jbgenzzof.css';
import '../../css/f/fwxuhy9_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qo16j27lx"/><path class="jbgenzzof"/><path class="fwxuhy9_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-in-bold" {...props}></Icon>
