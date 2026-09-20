<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw884i5gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw884i5gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:cell-formating-border-horizontal-vertical" {...props}></Icon>
