<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exv0g4bou.css';
import '../../css/y/ymkt-qbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exv0g4bou secondary"/><path class="primary ymkt-qbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:phone-duo" {...props}></Icon>
