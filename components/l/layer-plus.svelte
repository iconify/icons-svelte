<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae07h2byp.css';
import '../../css/a/a_f7wt5fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae07h2byp"/><path class="a_f7wt5fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:layer-plus" {...props}></Icon>
