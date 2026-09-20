<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1gqmmbxi.css';
import '../../css/n/nzl6tpgjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1gqmmbxi"/><path class="nzl6tpgjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bfic" {...props}></Icon>
