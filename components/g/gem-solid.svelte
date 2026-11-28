<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jougr8fnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jougr8fnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gem-solid" {...props}></Icon>
