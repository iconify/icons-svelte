<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz0q_bwle.css';
import '../../css/o/ofqsw8bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz0q_bwle"/><path class="ofqsw8bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:phone-ringing-high" {...props}></Icon>
