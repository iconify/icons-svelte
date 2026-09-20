<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dftf9rvck.css';
import '../../css/z/z3duhi67e.css';
import '../../css/c/c0f3cdbuc.css';
import '../../css/g/gnovq9q5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="dftf9rvck"/><path class="z3duhi67e"/><path class="c0f3cdbuc"/><path class="gnovq9q5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:atom" {...props}></Icon>
