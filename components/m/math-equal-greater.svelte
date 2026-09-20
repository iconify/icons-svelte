<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm9cjfb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm9cjfb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-equal-greater" {...props}></Icon>
