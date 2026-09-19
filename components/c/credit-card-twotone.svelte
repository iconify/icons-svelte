<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knaeq35ob.css';
import '../../css/p/p9-axprhp.css';
import '../../css/y/ynji0ebgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="knaeq35ob"/><path class="p9-axprhp"/><path class="ynji0ebgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:credit-card-twotone" {...props}></Icon>
