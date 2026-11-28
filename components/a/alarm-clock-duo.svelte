<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq4td4bfm.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lzl88sbdw.css';
import '../../css/k/kzudsg6mg.css';
import '../../css/n/n41jx5b9q.css';
import '../../css/r/r-ge1zblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary uq4td4bfm"/><g class="dt0cm9dhy primary"><circle class="lzl88sbdw"/><path class="kzudsg6mg"/><path class="n41jx5b9q"/><path class="r-ge1zblt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:alarm-clock-duo" {...props}></Icon>
