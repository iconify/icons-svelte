<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv6br_-mv.css';
import '../../css/c/ca-rzg1lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dv6br_-mv"/><path class="ca-rzg1lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:bank-outline" {...props}></Icon>
