<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dftf9rvck.css';
import '../../css/a/a11bti4rf.css';
import '../../css/s/stjv0pdcv.css';
import '../../css/p/pmr9h6bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="dftf9rvck"/><circle class="a11bti4rf"/><circle class="stjv0pdcv"/><path class="pmr9h6bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:message-circle-outline" {...props}></Icon>
