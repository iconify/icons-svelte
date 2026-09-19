<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogss53eaa.css';
import '../../css/q/qit74nb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogss53eaa"/><path class="qit74nb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:login" {...props}></Icon>
