<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixg1tmtgv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tfazt4b9n.css';
import '../../css/t/tuuqhnbvj.css';
import '../../css/t/tgej6jbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixg1tmtgv secondary"/><g class="dt0cm9dhy primary"><path class="tfazt4b9n"/><path class="tuuqhnbvj"/><path class="tgej6jbmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:building-duo" {...props}></Icon>
