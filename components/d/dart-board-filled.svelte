<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qit1y2bjj.css';
import '../../css/m/mlq8elbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qit1y2bjj"/><path class="mlq8elbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dart-board-filled" {...props}></Icon>
