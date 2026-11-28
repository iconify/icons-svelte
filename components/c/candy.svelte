<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq-kfj9bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq-kfj9bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:candy" {...props}></Icon>
