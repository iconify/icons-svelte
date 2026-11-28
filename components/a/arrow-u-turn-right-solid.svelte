<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqrpx5agk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqrpx5agk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-right-solid" {...props}></Icon>
