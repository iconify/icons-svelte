<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja5has27o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja5has27o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pay" {...props}></Icon>
