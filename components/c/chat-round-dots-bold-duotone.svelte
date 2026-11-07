<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ije5jlbjh.css';
import '../../css/f/fvfljmboy.css';
import '../../css/b/bj7uuyqyo.css';
import '../../css/q/qk12x8byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ije5jlbjh"/><path class="fvfljmboy"/><path class="bj7uuyqyo"/><path class="qk12x8byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-dots-bold-duotone" {...props}></Icon>
