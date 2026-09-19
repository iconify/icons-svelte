<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgj9wvwbi.css';
import '../../css/t/tvkysof6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgj9wvwbi"/><path class="tvkysof6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:log-in-circle" {...props}></Icon>
