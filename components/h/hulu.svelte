<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c65j88bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c65j88bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hulu" {...props}></Icon>
