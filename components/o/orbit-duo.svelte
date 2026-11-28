<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj4s0q_ul.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n8vpwlbbm.css';
import '../../css/q/q7y-vobgy.css';
import '../../css/g/gveaibcqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj4s0q_ul secondary"/><g class="dt0cm9dhy primary"><circle class="n8vpwlbbm"/><path class="q7y-vobgy"/><circle class="gveaibcqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:orbit-duo" {...props}></Icon>
