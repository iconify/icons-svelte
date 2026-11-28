<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g36qw7qxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g36qw7qxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-from-line-solid" {...props}></Icon>
