<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmpd__bdx.css';
import '../../css/a/a30rl-bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b fmpd__bdx"/><path class="a30rl-bmq b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:computer" {...props}></Icon>
