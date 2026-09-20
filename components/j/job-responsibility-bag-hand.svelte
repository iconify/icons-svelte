<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcsvxunqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcsvxunqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:job-responsibility-bag-hand" {...props}></Icon>
