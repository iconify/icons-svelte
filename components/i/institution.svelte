<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo6e8nbzk.css';
import '../../css/z/zhe7nq6ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo6e8nbzk"/><path class="zhe7nq6ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:institution" {...props}></Icon>
