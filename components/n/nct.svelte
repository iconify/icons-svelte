<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghx9yzbxt.css';
import '../../css/k/ktjyq3bmf.css';
import '../../css/v/v0b7vsbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghx9yzbxt"/><path class="ktjyq3bmf"/><path class="v0b7vsbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nct" {...props}></Icon>
