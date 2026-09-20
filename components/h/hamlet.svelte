<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/g9xv0vbnv.css';
import '../../css/j/j2px_1rfd.css';
import '../../css/w/w812ifbqt.css';
import '../../css/j/jlk8gwb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="g9xv0vbnv"/><path class="j2px_1rfd"/><circle class="w812ifbqt"/><circle class="jlk8gwb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:hamlet" {...props}></Icon>
