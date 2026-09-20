<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wr4181b4u.css';
import '../../css/k/ktpncgb0v.css';
import '../../css/a/arfwosbro.css';
import '../../css/a/aaakgqotp.css';
import '../../css/i/i8e2akblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wr4181b4u"/><path class="ktpncgb0v"/><path class="arfwosbro"/><circle class="aaakgqotp"/><path class="i8e2akblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-search-linear" {...props}></Icon>
