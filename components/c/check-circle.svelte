<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neifvedcl.css';
import '../../css/e/etgavr0mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="neifvedcl"/><path class="etgavr0mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:check-circle" {...props}></Icon>
