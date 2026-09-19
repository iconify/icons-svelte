<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj0bqhbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj0bqhbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:radio-unchecked" {...props}></Icon>
