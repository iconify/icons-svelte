<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emcz-1bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emcz-1bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:external-link-alt" {...props}></Icon>
