<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/f/fzr6uv.css';
import '../../css/w/wa90th.css';
import '../../css/s/so-from-50.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c fzr6uv"/><path class="a0m25c wa90th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:laptop" {...props}></Icon>
