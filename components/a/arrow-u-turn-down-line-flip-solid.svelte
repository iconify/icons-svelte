<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b082zcb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b082zcb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-down-line-flip-solid" {...props}></Icon>
