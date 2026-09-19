<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubq-_mz2b.css';
import '../../css/s/sbqm2wbdh.css';
import '../../css/e/eh56eccoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubq-_mz2b"/><circle class="sbqm2wbdh"/><circle class="eh56eccoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bus" {...props}></Icon>
