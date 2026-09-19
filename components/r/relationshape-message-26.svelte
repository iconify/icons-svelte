<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxi5mew3h.css';
import '../../css/l/ljoz4662n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<circle class="qxi5mew3h"/><circle class="ljoz4662n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:relationshape-message-26" {...props}></Icon>
