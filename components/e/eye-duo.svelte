<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab-gq9bkn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dmesvbbbc.css';
import '../../css/g/gz3bf3izr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab-gq9bkn secondary"/><g class="dt0cm9dhy primary"><path class="dmesvbbbc"/><circle class="gz3bf3izr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:eye-duo" {...props}></Icon>
